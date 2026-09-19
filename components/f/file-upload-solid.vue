<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbajkz4iu.css';
import '../../css/a/a4jsaxbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qbajkz4iu"/><path class="a4jsaxbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:file-upload-solid" /></template>
