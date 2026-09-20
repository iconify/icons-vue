<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-8yzyb5a.css';
import '../../css/j/jy7k-3hfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="e-8yzyb5a"/><path class="jy7k-3hfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-emergency" /></template>
