<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zie-95bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zie-95bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:castle-with-battlements" /></template>
