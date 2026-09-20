<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="n_a0g7bue"/><path class="mkv3xnbro"/><path class="p3oyjxb4g"/><path class="u185p2b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:fountain-pen" /></template>
<style>
.mkv3xnbro {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M22.511 5.308a2.946 2.946 0 0 0 0 4.167l4.167 4.168a2.95 2.95 0 0 0 4.167 0l4.167-4.168a2.95 2.95 0 0 0 0-4.167l-4.167-4.167a2.946 2.946 0 0 0-4.167 0z");
}

.n_a0g7bue {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M4.167 32.729c.292.167.626.271.987.271a2 2 0 1 0-2-2c0 .361.103.695.27.987L.278 35.133L1.154 28l9-7l5 5l-7 9l-7.134.876z");
}

.p3oyjxb4g {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M9.511 18.309L26.713 1.105l8.333 8.335l-17.201 17.203a2.95 2.95 0 0 1-4.168 0l-4.166-4.168a2.945 2.945 0 0 1 0-4.166");
}

.u185p2b2u {
  fill: var(--svg-color--66757f, #66757f);
  d: path("m17.469 10.35l2.125-2.125l8.334 8.334l-2.125 2.125z");
}

</style>
