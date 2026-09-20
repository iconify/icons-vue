<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go41ypbnd.css';
import '../../css/q/quv6-_b5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go41ypbnd"/><path class="quv6-_b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-add-filled" /></template>
