<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guq9ui5hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":832,"height":1024};
const content = `<path class="guq9ui5hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:coffeecupalt" /></template>
