<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac79qcb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ac79qcb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-microsoft" /></template>
