<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n004xq-kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="n004xq-kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:cplusplus-solid" /></template>
