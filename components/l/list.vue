<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvnjmgbvw.css';
import '../../css/g/gxpjv3bws.css';
import '../../css/b/b_mbvxopq.css';
import '../../css/d/db9bacbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvnjmgbvw wm-shadow"/><path class="gxpjv3bws wm-k"/><path class="b_mbvxopq wm-a"/><path class="db9bacbqt wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:list" /></template>
