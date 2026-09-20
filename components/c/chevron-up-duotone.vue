<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb_nxg3mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hb_nxg3mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chevron-up-duotone" /></template>
