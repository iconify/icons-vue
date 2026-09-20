<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_6jgtm7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x_6jgtm7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:corkscrew-outline" /></template>
