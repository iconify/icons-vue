<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acgrzsbvb.css';
import '../../css/o/ocxedjb1h.css';
import '../../css/i/i6107pbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="acgrzsbvb"/><path class="ocxedjb1h"/><path class="i6107pbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-trash" /></template>
