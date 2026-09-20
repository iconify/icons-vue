<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aixyo_bpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aixyo_bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:globe-outline" /></template>
