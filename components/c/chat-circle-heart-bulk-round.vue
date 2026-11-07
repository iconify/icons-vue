<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="aec7lkj0a"/><path class="t_5taybmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-heart-bulk-round" /></template>
<style>
.aec7lkj0a {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.196 21.981a1 1 0 0 1-1.177-1.177l.935-4.673A9.946 9.946 0 0 1 19.032 4.968A9.945 9.945 0 0 1 7.869 21.046Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.t_5taybmr {
  d: path("M12 9.398a3.7 3.7 0 0 1 2.375-.898C15.843 8.5 17 9.486 17 11c-.001 1.964-2.294 3.6-3.871 4.52q-.335.198-.682.374a1 1 0 0 1-.894 0A15.4 15.4 0 0 1 9.4 14.55C8.297 13.722 7.001 12.492 7 11c0-1.514 1.157-2.5 2.625-2.5c.869 0 1.718.335 2.375.898m0 4.465q.726-.416 1.4-.913c.433-.325.855-.682 1.194-1.106c.182-.228.406-.538.406-.844c0-.395-.267-.5-.625-.5c-.623 0-1.205.397-1.481.947a1 1 0 0 1-1.788 0a1.7 1.7 0 0 0-.663-.712a1.6 1.6 0 0 0-.818-.235c-.358 0-.625.105-.625.5c0 .306.224.616.406.844c.339.424.761.781 1.194 1.106q.674.497 1.4.913");
}

</style>
