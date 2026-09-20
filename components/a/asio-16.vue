<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lthfew8ud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lthfew8ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:asio-16" /></template>
