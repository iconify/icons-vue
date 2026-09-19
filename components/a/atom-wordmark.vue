<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6pslhx0v.css';
import '../../css/g/gboct0b5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="y6pslhx0v"/><path clip-rule="evenodd" class="gboct0b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:atom-wordmark" /></template>
