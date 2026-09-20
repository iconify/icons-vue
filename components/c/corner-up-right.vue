<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odlhkk26y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="odlhkk26y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:corner-up-right" /></template>
