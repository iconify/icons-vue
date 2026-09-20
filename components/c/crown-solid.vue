<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmltz5b2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmltz5b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:crown-solid" /></template>
