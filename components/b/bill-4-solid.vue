<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luawv7jmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="luawv7jmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bill-4-solid" /></template>
