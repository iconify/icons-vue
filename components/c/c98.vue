<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdsb-idre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rdsb-idre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:c98" /></template>
