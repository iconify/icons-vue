<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4ioyfbzk.css';
import '../../css/h/hie35vbnj.css';
import '../../css/k/k1t7ff4oh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4ioyfbzk wm-k"/><path class="hie35vbnj wm-k"/><path class="k1t7ff4oh wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:dog" /></template>
