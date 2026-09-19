<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfm_umb2w.css';
import '../../css/z/zjqxlr-ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfm_umb2w"/><path clip-rule="evenodd" class="zjqxlr-ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:gift-filled" /></template>
