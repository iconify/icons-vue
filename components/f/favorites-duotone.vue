<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wit9n4b-r.css';
import '../../css/i/ig9_8-b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wit9n4b-r"/><path class="ig9_8-b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:favorites-duotone" /></template>
