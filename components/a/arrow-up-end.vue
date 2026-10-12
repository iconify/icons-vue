<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhxe1gb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhxe1gb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:arrow-up-end" /></template>
