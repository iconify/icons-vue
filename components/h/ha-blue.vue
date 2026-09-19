<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ampx37alc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ampx37alc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ha-blue" /></template>
