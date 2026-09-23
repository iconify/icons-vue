<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceduwrv8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ceduwrv8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:eject-sharp-fill" /></template>
