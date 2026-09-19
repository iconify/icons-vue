<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6b_w7i5u.css';
import '../../css/u/u2s7mrrsa.css';
import '../../css/l/ly1jq7bwb.css';
import '../../css/p/pc047fbaf.css';
import '../../css/l/lw7f7x36m.css';
import '../../css/x/xw6fnqbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<circle class="e6b_w7i5u"/><circle class="u2s7mrrsa"/><circle class="ly1jq7bwb"/><circle class="pc047fbaf"/><circle class="lw7f7x36m"/><circle class="xw6fnqbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:braille" /></template>
