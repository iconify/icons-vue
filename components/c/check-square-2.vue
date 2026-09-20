<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du_6b3bct.css';
import '../../css/a/apxnxjkhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du_6b3bct"/><path class="apxnxjkhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:check-square-2" /></template>
