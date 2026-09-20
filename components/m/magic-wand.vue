<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="boy5yg3wz"/><path class="zpgr9hsut"/><path class="wg4y4kb9a"/><path class="x35fuybkr"/><path class="gxkvvliai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:magic-wand" /></template>
<style>
.boy5yg3wz {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M3.651 29.852L29.926 3.576c.391-.391 2.888 2.107 2.497 2.497L6.148 32.349c-.39.391-2.888-2.107-2.497-2.497");
}

.gxkvvliai {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("m28.897 14.913l1.542-.571l.6-2.2a.667.667 0 0 1 1.287 0l.6 2.2l1.542.571a.665.665 0 0 1 0 1.25l-1.534.568l-.605 2.415a.667.667 0 0 1-1.293 0l-.605-2.415l-1.534-.568a.665.665 0 0 1 0-1.25M11.961 5.285l2.61-.966l.966-2.61a1.103 1.103 0 0 1 2.07 0l.966 2.61l2.609.966a1.103 1.103 0 0 1 0 2.07l-2.609.966l-.966 2.61a1.105 1.105 0 0 1-2.07 0l-.966-2.61l-2.61-.966a1.104 1.104 0 0 1 0-2.07M24.13 20.772l1.383-.512l.512-1.382a.585.585 0 0 1 1.096 0l.512 1.382l1.382.512a.584.584 0 0 1 0 1.096l-1.382.512l-.512 1.382a.585.585 0 0 1-1.096 0l-.512-1.382l-1.383-.512a.585.585 0 0 1 0-1.096");
}

.wg4y4kb9a {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("m34.546 2.537l-.412-.412l-.671-.671a1 1 0 0 0-.255-.169a.99.99 0 0 0-1.159.169l-2.102 2.102l.495.495l.883.883l1.119 1.119l2.102-2.102a1 1 0 0 0 0-1.414M5.029 31.23l-.883-.883l-.495-.495l-2.209 2.208a.99.99 0 0 0-.169 1.159c.046.09.094.18.169.255l.671.671l.412.412a1 1 0 0 0 1.414 0l2.208-2.208z");
}

.x35fuybkr {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("m31.325 4.934l2.809-2.809l-.671-.671a1 1 0 0 0-.255-.169l-2.767 2.767zM4.146 30.347L1.273 33.22c.046.09.094.18.169.255l.671.671l2.916-2.916z");
}

.zpgr9hsut {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M30.442 4.051L4.146 30.347l.883.883L31.325 4.934z");
}

</style>
