<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adl5jsb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adl5jsb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-squares-check-sharp" /></template>
