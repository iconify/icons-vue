<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc48rr7mb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yc48rr7mb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-stop" /></template>
