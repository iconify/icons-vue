<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8pmzds9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b8pmzds9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:eye-slash-solid" /></template>
