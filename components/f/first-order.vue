<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgxw63bss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kgxw63bss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:first-order" /></template>
