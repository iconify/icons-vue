<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aisis0a7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aisis0a7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:checkbox-checked-solid" /></template>
