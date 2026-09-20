<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-log0e6r.css';
import '../../css/e/e4me81bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-log0e6r"/><path clip-rule="evenodd" class="e4me81bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:globe-stand" /></template>
