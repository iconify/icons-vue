<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_6ah42xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n_6ah42xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:facebook-outline" /></template>
