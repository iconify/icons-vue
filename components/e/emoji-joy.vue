<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7z4v_blb.css';
import '../../css/j/jhodmt__j.css';
import '../../css/b/btlc75bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7z4v_blb"/><path clip-rule="evenodd" class="jhodmt__j"/><path clip-rule="evenodd" class="btlc75bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:emoji-joy" /></template>
