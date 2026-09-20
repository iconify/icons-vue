<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wamhf9-td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wamhf9-td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:arrow-up-right-24" /></template>
