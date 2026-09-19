<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckg3ubbyx.css';
import '../../css/g/gcn7qhbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckg3ubbyx"/><path clip-rule="evenodd" class="gcn7qhbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:comment-block-outline" /></template>
