<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai4s28y9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ai4s28y9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:comment-check-filled" /></template>
