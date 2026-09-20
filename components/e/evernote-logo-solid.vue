<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2z5elgja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c2z5elgja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:evernote-logo-solid" /></template>
