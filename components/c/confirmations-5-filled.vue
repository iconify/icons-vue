<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmf71jbnp.css';
import '../../css/d/d6aw1qt_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmf71jbnp"/><path clip-rule="evenodd" class="d6aw1qt_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:confirmations-5-filled" /></template>
