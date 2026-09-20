<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvhw3bccs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvhw3bccs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:fdroid" /></template>
