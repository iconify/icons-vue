<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1jf6ebeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1600};
const content = `<path class="e1jf6ebeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:html5" /></template>
