<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsgld8g3i.css';
import '../../css/t/tehcrdk0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsgld8g3i"/><path clip-rule="evenodd" class="tehcrdk0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:dollar-alt-1-fill" /></template>
