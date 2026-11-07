<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqdm2xbfi.css';
import '../../css/p/prq9nybvi.css';
import '../../css/d/d71ngcbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqdm2xbfi"/><path class="prq9nybvi"/><path clip-rule="evenodd" class="d71ngcbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:danger-outline" /></template>
