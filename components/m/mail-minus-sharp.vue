<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovyazib-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovyazib-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-minus-sharp" /></template>
