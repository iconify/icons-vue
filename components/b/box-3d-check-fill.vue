<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt59svwig.css';
import '../../css/d/d5bwuacpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt59svwig"/><path class="d5bwuacpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:box-3d-check-fill" /></template>
