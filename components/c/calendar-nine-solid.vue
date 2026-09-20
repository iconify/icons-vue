<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fivtch93m.css';
import '../../css/c/ctzgkpf1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fivtch93m"/><path class="ctzgkpf1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:calendar-nine-solid" /></template>
