<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deb0atb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="deb0atb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:info-sharp-fill" /></template>
