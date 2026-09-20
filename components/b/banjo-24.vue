<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic_64ladj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic_64ladj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:banjo-24" /></template>
