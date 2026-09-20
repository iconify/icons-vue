<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn1c5os8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn1c5os8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:exclamation-triangle-fill" /></template>
