<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":174};
const content = `<path class="rb3hxw7fu"/><path class="fb_wvxbai"/><path class="x1vz2wbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:kemal" /></template>
<style>
.fb_wvxbai {
  fill: var(--svg-color--f92727, #f92727);
  d: path("M128.594 0v173.994H256L235.06 3.674A4.185 4.185 0 0 0 230.904 0z");
}

.rb3hxw7fu {
  fill: var(--svg-color--ff4f4f, #ff4f4f);
  d: path("m128.594 0l1.393 3.076l.194 167.825l-1.587 3.093H0L20.941 3.674A4.185 4.185 0 0 1 25.095 0z");
}

.x1vz2wbml {
  d: path("M197.051 105.538h-5.616L191.346 0h4.725z");
}

</style>
