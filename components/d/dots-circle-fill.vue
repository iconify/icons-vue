<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viud3_gtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="viud3_gtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dots-circle-fill" /></template>
