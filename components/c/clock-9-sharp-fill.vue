<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn14jqb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kn14jqb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-9-sharp-fill" /></template>
