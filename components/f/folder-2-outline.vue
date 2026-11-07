<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssso-fkbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ssso-fkbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-2-outline" /></template>
