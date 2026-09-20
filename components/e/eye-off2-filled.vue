<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht4j2lblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ht4j2lblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:eye-off2-filled" /></template>
