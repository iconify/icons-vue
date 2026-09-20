<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3ygc7boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3ygc7boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:buildings-sharp-fill" /></template>
