<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wto57b17c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="wto57b17c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:danger-11" /></template>
