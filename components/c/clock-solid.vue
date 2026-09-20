<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqg48nbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="tqg48nbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:clock-solid" /></template>
