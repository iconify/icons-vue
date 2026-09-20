<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csgxesbgh.css';
import '../../css/c/ctzgkpf1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csgxesbgh"/><path class="ctzgkpf1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:calendar-star-solid" /></template>
