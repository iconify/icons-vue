<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj5qrwuif.css';
import '../../css/z/z1iti509n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj5qrwuif"/><path clip-rule="evenodd" class="z1iti509n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-bottom-detailed-fill" /></template>
