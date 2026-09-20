<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oql7-e3yp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oql7-e3yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:fireflyiii" /></template>
