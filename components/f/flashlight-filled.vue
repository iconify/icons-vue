<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dodjpsu0u.css';
import '../../css/a/a3b73cb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dodjpsu0u"/><path class="a3b73cb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:flashlight-filled" /></template>
