<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvhwunbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvhwunbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:blender-phone-outline" /></template>
