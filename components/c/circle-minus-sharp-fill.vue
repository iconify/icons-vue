<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb0l61w-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nb0l61w-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-minus-sharp-fill" /></template>
