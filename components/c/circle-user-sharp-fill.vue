<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0m83wyra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k0m83wyra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-user-sharp-fill" /></template>
