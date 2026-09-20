<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8pbo6bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8pbo6bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:apachecouchdb" /></template>
