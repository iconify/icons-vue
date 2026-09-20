<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2ry_ybrz.css';
import '../../css/b/b9icdeqxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2ry_ybrz"/><path class="b9icdeqxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:envelope-flying" /></template>
