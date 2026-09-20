<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmi0wdbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmi0wdbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:file-check-fill" /></template>
