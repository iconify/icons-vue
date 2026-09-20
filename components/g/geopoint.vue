<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfc3txbai.css';
import '../../css/f/f43eqhbwn.css';
import '../../css/y/yx6wxur-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dfc3txbai"/><circle class="f43eqhbwn"/><path clip-rule="evenodd" class="yx6wxur-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:geopoint" /></template>
