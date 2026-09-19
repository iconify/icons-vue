<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiswtmbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aiswtmbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:form-view-hide" /></template>
