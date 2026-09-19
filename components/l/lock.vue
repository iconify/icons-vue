<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma4oo9-dx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ma4oo9-dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:lock" /></template>
