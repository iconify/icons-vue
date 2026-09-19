<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brmy6cpyy.css';
import '../../css/p/p-6rxcb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="brmy6cpyy"/><path class="p-6rxcb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-ionitron-outline" /></template>
