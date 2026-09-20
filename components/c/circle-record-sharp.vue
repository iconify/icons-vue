<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b77o_4b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b77o_4b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-record-sharp" /></template>
