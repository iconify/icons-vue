<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paskc84gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="paskc84gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:betfair" /></template>
