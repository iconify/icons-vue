<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_4ht5bkm.css';
import '../../css/q/q2dc-8bor.css';
import '../../css/b/b0jxrubul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_4ht5bkm"/><path class="q2dc-8bor"/><path class="b0jxrubul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-deploy" /></template>
