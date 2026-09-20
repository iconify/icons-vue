<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qika6xbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qika6xbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bomb-outline" /></template>
