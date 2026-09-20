<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0n9b51wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o0n9b51wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:float-left-solid" /></template>
