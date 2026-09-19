<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyuoiib2w.css';
import '../../css/b/b6kmhlhnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyuoiib2w"/><path clip-rule="evenodd" class="b6kmhlhnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:confirmations-1-filled" /></template>
