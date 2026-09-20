<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzjrpw80r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzjrpw80r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fireship" /></template>
