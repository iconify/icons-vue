<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3e5i7vvy.css';
import '../../css/e/esqxa_cse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="n3e5i7vvy"/><path class="esqxa_cse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:immunizations" /></template>
