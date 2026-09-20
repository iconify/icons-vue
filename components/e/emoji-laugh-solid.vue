<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxea_3b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qxea_3b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:emoji-laugh-solid" /></template>
