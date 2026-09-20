<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic_tog6rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ic_tog6rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:checklist-alt-filled" /></template>
