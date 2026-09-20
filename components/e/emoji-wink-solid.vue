<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuc5lzbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nuc5lzbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:emoji-wink-solid" /></template>
