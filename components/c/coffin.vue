<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="m76cvjbxa"/><path class="mp6k3m2ue"/><path class="xdxb9pb7f"/><path class="ajkt65bzq"/><path class="mcsgfcb8o"/><path class="ud96hs22e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:coffin" /></template>
<style>
.ajkt65bzq {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("m34 5l-4.412 9.824L7.353 28.588L1 22L17.941 2.118L28.529 0z");
}

.m76cvjbxa {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("m31 12l-1.412 10.235L7.353 36L5 28z");
}

.mcsgfcb8o {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M12.001 30a1 1 0 0 1-.556-1.832l3-2a1 1 0 1 1 1.11 1.664l-3 2a1 1 0 0 1-.554.168m11-7a1 1 0 0 1-.556-1.832l3-2a1 1 0 0 1 1.11 1.664l-3 2a1 1 0 0 1-.554.168");
}

.mp6k3m2ue {
  fill: var(--svg-color--662113, #662113);
  d: path("M1 22v7.647L7.353 36v-8z");
}

.ud96hs22e {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M9 25c-.258 0-.514-.1-.708-.293l-3-3a1 1 0 0 1-.022-1.391l15-16a1 1 0 0 1 .565-.302l6-1a1 1 0 0 1 .871.279l2 2a1 1 0 0 1 .223 1.079l-2 5a1 1 0 0 1-.343.439l-18 13A1 1 0 0 1 9 25m-1.608-4.022l1.713 1.713L26.18 10.359l1.646-4.119l-1.169-1.17l-5.159.86z");
}

.xdxb9pb7f {
  fill: var(--svg-color--a04e3c, #a04e3c);
  d: path("M34 5v7.706l-4.412 9.529V15L31 9z");
}

</style>
