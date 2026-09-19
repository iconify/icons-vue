<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyi44ab9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yyi44ab9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hand-spock" /></template>
