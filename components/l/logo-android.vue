<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weah1dbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="weah1dbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:logo-android" /></template>
