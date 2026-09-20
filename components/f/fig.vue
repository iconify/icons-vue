<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5bzhc2yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5bzhc2yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:fig" /></template>
