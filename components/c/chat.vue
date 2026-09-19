<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr0j3ubit.css';
import '../../css/g/go-hdki3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sr0j3ubit"/><path class="go-hdki3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:chat" /></template>
