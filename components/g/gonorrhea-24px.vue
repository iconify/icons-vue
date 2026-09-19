<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1f_37bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e1f_37bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:gonorrhea-24px" /></template>
