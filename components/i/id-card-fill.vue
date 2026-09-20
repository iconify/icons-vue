<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8i3s3bzy.css';
import '../../css/b/bgzw1sbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8i3s3bzy"/><path class="bgzw1sbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:id-card-fill" /></template>
