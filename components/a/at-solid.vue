<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6jfslbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="o6jfslbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:at-solid" /></template>
