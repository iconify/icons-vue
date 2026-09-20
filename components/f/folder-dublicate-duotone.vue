<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am28lx2fj.css';
import '../../css/n/ncr5l6peb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am28lx2fj"/><path class="ncr5l6peb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:folder-dublicate-duotone" /></template>
