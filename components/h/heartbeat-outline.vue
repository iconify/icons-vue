<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1bf0p4rg.css';
import '../../css/g/gf6bg710v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1bf0p4rg"/><path class="gf6bg710v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:heartbeat-outline" /></template>
