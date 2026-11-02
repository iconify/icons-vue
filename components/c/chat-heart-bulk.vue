<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="okjsc7yvd"/><path class="extrw88rt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-heart-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.extrw88rt {
  d: path("M12 7.398a3.7 3.7 0 0 1 2.375-.898C15.843 6.5 17 7.486 17 9c-.001 1.964-2.294 3.6-3.871 4.52q-.335.198-.682.374a1 1 0 0 1-.894 0A15.4 15.4 0 0 1 9.4 12.55C8.297 11.722 7.001 10.492 7 9c0-1.514 1.157-2.5 2.625-2.5c.869 0 1.718.335 2.375.898m0 4.465q.726-.416 1.4-.913c.433-.325.855-.682 1.194-1.106c.182-.228.406-.538.406-.844c0-.395-.267-.5-.625-.5c-.623 0-1.205.397-1.481.947a1 1 0 0 1-1.788 0a1.7 1.7 0 0 0-.663-.712a1.6 1.6 0 0 0-.818-.235C9.267 8.5 9 8.605 9 9c0 .306.224.616.406.844c.339.424.761.781 1.194 1.106q.674.497 1.4.913");
}

.okjsc7yvd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 18H8c-.468 0-.98.395-1.293.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 20.928 2 19.898 2 19V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3");
}

</style>
