<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj8uj2zta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="xj8uj2zta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:database-solid" /></template>
