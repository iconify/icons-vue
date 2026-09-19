<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzaq1gb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzaq1gb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:eject" /></template>
