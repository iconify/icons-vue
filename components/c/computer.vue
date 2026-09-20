<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs2lxvbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="bs2lxvbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:computer" /></template>
