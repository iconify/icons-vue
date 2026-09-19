<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2bqgmpvm.css';
import '../../css/o/ove83va-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":13};
const content = `<path class="k2bqgmpvm"/><path class="ove83va-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:eye" /></template>
