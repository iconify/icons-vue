<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n913frb6j.css';
import '../../css/o/oxtj35b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n913frb6j"/><path class="oxtj35b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-lock-filled" /></template>
