<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drwktt30k.css';
import '../../css/x/xcjpxq55x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drwktt30k"/><path class="xcjpxq55x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-optimization-ai-fleet-routing-api" /></template>
