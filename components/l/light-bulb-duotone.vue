<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzi254bkh.css';
import '../../css/j/j-f4z-bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzi254bkh"/><path class="j-f4z-bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:light-bulb-duotone" /></template>
