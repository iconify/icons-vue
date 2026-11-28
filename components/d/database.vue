<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh9h2u3sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh9h2u3sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:database" /></template>
