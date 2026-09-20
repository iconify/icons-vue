<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-8b3ot2c.css';
import '../../css/u/u7z4v_blb.css';
import '../../css/j/jhodmt__j.css';
import '../../css/b/btlc75bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w-8b3ot2c"/><path class="u7z4v_blb"/><path clip-rule="evenodd" class="jhodmt__j"/><path clip-rule="evenodd" class="btlc75bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:emoji-joy-duotone" /></template>
